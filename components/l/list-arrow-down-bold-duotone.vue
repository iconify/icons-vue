<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dtjo_wb4r.css';
import '../../css/n/np3s9-e3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dtjo_wb4r"/><path class="np3s9-e3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:list-arrow-down-bold-duotone" /></template>

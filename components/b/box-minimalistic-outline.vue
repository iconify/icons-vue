<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oz4rxo_yp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oz4rxo_yp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:box-minimalistic-outline" /></template>

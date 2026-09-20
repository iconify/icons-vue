<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-uatcbyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z-uatcbyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:dumbbells-2-outline" /></template>

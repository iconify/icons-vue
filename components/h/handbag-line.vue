<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kx_wdcbwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kx_wdcbwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:handbag-line" /></template>

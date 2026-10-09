<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mkcxx1bzb.css';
import '../../css/w/wo_d300qx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mkcxx1bzb"/><path class="wo_d300qx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:battery-warning-20" /></template>

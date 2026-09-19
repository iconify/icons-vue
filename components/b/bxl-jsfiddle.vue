<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xr2-x0j6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xr2-x0j6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-jsfiddle" /></template>

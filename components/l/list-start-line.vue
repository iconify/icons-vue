<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ycf1h_bmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ycf1h_bmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:list-start-line" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/te315qpuv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="te315qpuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:apple-music" /></template>

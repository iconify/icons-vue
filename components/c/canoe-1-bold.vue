<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwk-aybvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="uwk-aybvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:canoe-1-bold" /></template>

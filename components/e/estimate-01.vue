<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/j/j5r9vy1yt.css';
import '../../css/g/gqbjnibrr.css';
import '../../css/r/r0dvnpb_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="j5r9vy1yt"/><path class="gqbjnibrr"/><path class="r0dvnpb_w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:estimate-01" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/w/wh9opwgvq.css';
import '../../css/o/oa9-0xdcp.css';
import '../../css/z/zya3c2i3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="wh9opwgvq"/><path class="oa9-0xdcp"/><path class="zya3c2i3b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:asteroid-01" /></template>

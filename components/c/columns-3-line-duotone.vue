<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/dcxilvb-z.css';
import '../../css/o/o__f46b3u.css';
import '../../css/r/rma5_ql1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="dcxilvb-z"/><path class="o__f46b3u"/><path class="rma5_ql1e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:columns-3-line-duotone" /></template>

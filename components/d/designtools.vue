<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/lw-gki7ii.css';
import '../../css/b/bb-gp60lh.css';
import '../../css/r/r0csu8bbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="lw-gki7ii"/><path class="bb-gp60lh"/><path class="r0csu8bbg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:designtools" /></template>

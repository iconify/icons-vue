<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gopnm44um.css';
import '../../css/i/i5p4ugbzq.css';
import '../../css/q/qm1o60b0x.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGBdMjMcXG"><g class="gopnm44um"><rect class="i5p4ugbzq"/><path class="qm1o60b0x"/></g></mask></defs><path mask="url(#SVGBdMjMcXG)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:alignment-top-left" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/n28yuybeb.css';
import '../../css/o/og93wpq7z.css';
import '../../css/e/eeipk_bjn.css';
import '../../css/j/j2jofiwpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="n28yuybeb"/><path clip-rule="evenodd" class="og93wpq7z"/><path class="eeipk_bjn"/><path clip-rule="evenodd" class="j2jofiwpv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:box-layout-3-duo" /></template>

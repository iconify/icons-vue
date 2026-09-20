<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rptjgybth.css';
import '../../css/i/it5wwus0x.css';
import '../../css/s/shxeislua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="rptjgybth"/><path class="it5wwus0x"/><path class="shxeislua"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:document-location" /></template>

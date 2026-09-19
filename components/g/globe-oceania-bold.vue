<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/x8avjbd1d.css';
import '../../css/n/nicn_dwwh.css';
import '../../css/q/qvppyhxrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="x8avjbd1d"/><path clip-rule="evenodd" class="nicn_dwwh"/><path class="qvppyhxrp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:globe-oceania-bold" /></template>

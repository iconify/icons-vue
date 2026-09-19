<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/v9iwk1bwv.css';
import '../../css/y/yvg5bdcoq.css';
import '../../css/o/oxa7wjbyu.css';
import '../../css/l/lte0itjcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="v9iwk1bwv"/><path class="yvg5bdcoq"/><path class="oxa7wjbyu"/><path class="lte0itjcq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:binoculars-duo" /></template>

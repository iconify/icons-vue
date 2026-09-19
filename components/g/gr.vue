<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/wqwf-7vsq.css';
import '../../css/e/ey2ol9b3k.css';
import '../../css/u/uado6y5ui.css';
import '../../css/i/is6hdcc7l.css';
import '../../css/c/cpezpi5si.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="wqwf-7vsq"/><path clip-rule="evenodd" class="ey2ol9b3k"/><path class="uado6y5ui"/><path clip-rule="evenodd" class="is6hdcc7l"/><path clip-rule="evenodd" class="cpezpi5si"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flagpack:gr" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/e1qp3l54h.css';
import '../../css/t/tj4vulnki.css';
import '../../css/o/okr_p42se.css';
import '../../css/q/qff5zwbcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="e1qp3l54h"/><path clip-rule="evenodd" class="tj4vulnki"/><path class="okr_p42se"/><path clip-rule="evenodd" class="qff5zwbcp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:chevron-square-outline" /></template>

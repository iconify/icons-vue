<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fpta62pcs.css';
import '../../css/c/c6-vmvbdd.css';
import '../../css/f/fh57rqojb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="fpta62pcs"/><path class="c6-vmvbdd"/><path class="fh57rqojb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:door-open-duo" /></template>

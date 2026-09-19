<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/gpo1i1b2q.css';
import '../../css/f/fa29q174i.css';
import '../../css/x/xq8n2obgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="gpo1i1b2q"/><path class="fa29q174i"/><path class="xq8n2obgg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:box-close-duo" /></template>

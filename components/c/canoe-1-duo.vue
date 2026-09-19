<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/swr84yb6f.css';
import '../../css/h/hn5zmzb1j.css';
import '../../css/m/mk5yu_unr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="swr84yb6f"/><path class="hn5zmzb1j"/><path class="mk5yu_unr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:canoe-1-duo" /></template>

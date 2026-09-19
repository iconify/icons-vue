<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rhl8btbnt.css';
import '../../css/b/bdsyk5b6o.css';
import '../../css/h/h-tc3zb4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="rhl8btbnt"/><path class="bdsyk5b6o"/><path class="h-tc3zb4v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:loveseat-duo" /></template>

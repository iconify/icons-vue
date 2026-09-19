<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rzlor2bis.css';
import '../../css/t/trnyoum9w.css';
import '../../css/e/e3rxiqbbg.css';
import '../../css/h/h_3kmvbkb.css';
import '../../css/d/dp11gvrnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="rzlor2bis"/><path class="trnyoum9w"/><path clip-rule="evenodd" class="e3rxiqbbg"/><path class="h_3kmvbkb"/><path class="dp11gvrnz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:globe-stand-middle-duo" /></template>

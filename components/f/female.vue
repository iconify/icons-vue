<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/e5k9mhbdo.css';
import '../../css/o/ob8xw0bkr.css';
import '../../css/r/r3s12lbsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="e5k9mhbdo"/><path class="ob8xw0bkr"/><path class="r3s12lbsu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:female" /></template>

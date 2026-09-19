<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/o0z66u04y.css';
import '../../css/p/ppta7nblo.css';
import '../../css/x/xqmsk0-rl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="o0z66u04y"/><path class="ppta7nblo"/><path class="xqmsk0-rl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:house-flood-duo" /></template>

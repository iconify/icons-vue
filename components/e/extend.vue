<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/nv1deiyek.css';
import '../../css/k/kg14vw5et.css';
import '../../css/p/pfjz1wg0j.css';
import '../../css/d/d5f13wc2z.css';
import '../../css/u/ucjr577xf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><rect class="nv1deiyek"/><path class="kg14vw5et"/><path class="pfjz1wg0j"/><path class="d5f13wc2z"/><path class="ucjr577xf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:extend" /></template>

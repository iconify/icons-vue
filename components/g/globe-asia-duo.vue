<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/ij883nb6j.css';
import '../../css/m/mebepjbpv.css';
import '../../css/l/lld-bqbtb.css';
import '../../css/u/u90b6tbsy.css';
import '../../css/r/r1zeu3bzj.css';
import '../../css/p/pzvibbb2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="ij883nb6j"/><path class="mebepjbpv"/><path class="lld-bqbtb"/><path class="u90b6tbsy"/><path class="r1zeu3bzj"/><path class="pzvibbb2k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:globe-asia-duo" /></template>

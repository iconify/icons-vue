<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/m/mk_pnxbej.css';
import '../../css/n/nhmln6bau.css';
import '../../css/x/xofm-lbrq.css';
import '../../css/l/lj2ryhrph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="mk_pnxbej"/><path class="nhmln6bau"/><path class="xofm-lbrq"/><path class="lj2ryhrph"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:farm-outline" /></template>

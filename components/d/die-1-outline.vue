<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/w/w5l36fhuc.css';
import '../../css/k/k8ta0qmcg.css';
import '../../css/p/pg1uithbf.css';
import '../../css/s/sxclq_x3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="w5l36fhuc"/><path class="k8ta0qmcg"/><path class="pg1uithbf"/><path class="sxclq_x3o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:die-1-outline" /></template>

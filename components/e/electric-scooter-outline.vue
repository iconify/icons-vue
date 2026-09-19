<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/u/uu-ccsewz.css';
import '../../css/h/h_wfhzbpa.css';
import '../../css/c/ck7jbacvf.css';
import '../../css/c/c-pklybfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="uu-ccsewz"/><path class="h_wfhzbpa"/><path class="ck7jbacvf"/><path class="c-pklybfk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:electric-scooter-outline" /></template>

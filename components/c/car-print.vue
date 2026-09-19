<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/e/e6i1gi7-e.css';
import '../../css/r/rslh1bblg.css';
import '../../css/w/wdbmhubrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="e6i1gi7-e"/><path class="rslh1bblg"/><path class="wdbmhubrq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:car-print" /></template>

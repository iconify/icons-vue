<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/e/e7ra0203t.css';
import '../../css/l/l_oo4cchq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":25};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="e7ra0203t"/><path class="l_oo4cchq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:bookmark-circle" /></template>

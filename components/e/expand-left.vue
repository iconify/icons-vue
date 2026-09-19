<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/a/a1a7fuk7x.css';
import '../../css/o/ouk324llz.css';
import '../../css/j/jg5riebmr.css';
import '../../css/d/d99d2rtqd.css';
import '../../css/o/oy5jdmb9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="a1a7fuk7x"/><path class="ouk324llz"/><path class="jg5riebmr"/><path class="d99d2rtqd"/><path class="oy5jdmb9j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:expand-left" /></template>

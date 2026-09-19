<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/u/urswrcbmq.css';
import '../../css/t/t211_glzn.css';
import '../../css/s/sectwdvrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="h01tyzbfu"><circle class="urswrcbmq"/><path class="t211_glzn"/><ellipse class="sectwdvrp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:globe-stroke-16" /></template>

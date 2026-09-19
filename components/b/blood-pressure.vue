<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/au-phnwrn.css';
import '../../css/v/v2o4ilcrp.css';
import '../../css/a/aqpsapbet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="au-phnwrn"/><path class="v2o4ilcrp"/><path clip-rule="evenodd" class="aqpsapbet"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:blood-pressure" /></template>

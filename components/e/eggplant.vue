<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/d/ddmw1lqul.css';
import '../../css/v/vrk49ebtl.css';
import '../../css/h/h12wcpb0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="ddmw1lqul"/><path class="vrk49ebtl"/><path class="h12wcpb0y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:eggplant" /></template>

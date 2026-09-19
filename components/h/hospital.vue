<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/k/kt_m-joux.css';
import '../../css/m/mh7ucwbev.css';
import '../../css/q/ql6hqqjvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="kt_m-joux"/><path class="mh7ucwbev"/><path class="ql6hqqjvi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:hospital" /></template>

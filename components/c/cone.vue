<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/a/amd3c_7ux.css';
import '../../css/a/azfqzgbgh.css';
import '../../css/l/l6kmrgbaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><ellipse class="amd3c_7ux"/><path class="azfqzgbgh"/><path class="l6kmrgbaq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:cone" /></template>

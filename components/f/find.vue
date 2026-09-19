<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/m/mxaazra7v.css';
import '../../css/l/l54ohfuze.css';
import '../../css/v/v-cwrbbvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="mxaazra7v"/><path class="l54ohfuze"/><path class="v-cwrbbvd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:find" /></template>

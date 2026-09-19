<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/v/vuz12tb0u.css';
import '../../css/k/ki59usoeo.css';
import '../../css/q/qgc7wpbsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="vuz12tb0u"/><path class="ki59usoeo"/><path class="qgc7wpbsb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:certificate" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/s/spfnwnbrc.css';
import '../../css/q/qy-xuybra.css';
import '../../css/h/hk92wwirk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="spfnwnbrc"/><path class="qy-xuybra"/><path class="hk92wwirk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:bring-to-front" /></template>

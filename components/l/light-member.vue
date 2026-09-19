<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/l/l4o2qpb4m.css';
import '../../css/t/tqg4a-7db.css';
import '../../css/q/qkenzxbrz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="l4o2qpb4m"/><path class="tqg4a-7db"/><path class="qkenzxbrz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:light-member" /></template>

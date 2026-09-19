<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3lph30dl.css';
import '../../css/e/en4rke54j.css';
import '../../css/n/n4-moed9v.css';
import '../../css/i/ijo2s9bfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="l3lph30dl"><path class="en4rke54j"/><path class="n4-moed9v"/><rect class="ijo2s9bfw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:distribute-vertical-spacing" /></template>

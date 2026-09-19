<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o93lq-byo.css';
import '../../css/a/amd3c_7ux.css';
import '../../css/w/wjkzsobel.css';
import '../../css/i/ihj7g8l1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><ellipse class="amd3c_7ux"/><path class="wjkzsobel"/><path class="ihj7g8l1o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:cone" /></template>

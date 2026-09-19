<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nibs_lbmi.css';
import '../../css/a/as15v3bwn.css';
import '../../css/q/qrc405bkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<g class="nibs_lbmi"><path class="as15v3bwn"/><path class="qrc405bkt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:go-wordmark" /></template>

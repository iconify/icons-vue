<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sz-_5oksg.css';
import '../../css/n/no7vk9bpc.css';
import '../../css/s/sb52f8dlw.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/u/usozxnbrm.css';
import '../../css/q/q72ijub7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<circle class="sz-_5oksg"/><path class="no7vk9bpc"/><path class="sb52f8dlw"/><g class="ij2x_72vy"><circle class="usozxnbrm"/><path class="q72ijub7o"/><circle class="usozxnbrm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:globe-showing-asia-australia" /></template>

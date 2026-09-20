<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wism3vaym.css';
import '../../css/l/lze8anq-p.css';
import '../../css/q/q_x6h4byx.css';
import '../../css/q/qy525jbwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="wism3vaym"/><path class="lze8anq-p"/><path transform="matrix(.9199 0 0 .9196 1.096 1.101)" class="q_x6h4byx"/><path class="qy525jbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:esperanto-flag" /></template>

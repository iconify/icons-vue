<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yefe715tw.css';
import '../../css/q/qpzpo_b1f.css';
import '../../css/x/x8poo_bjf.css';
import '../../css/t/t08z06bxh.css';
import '../../css/h/ho69mj0-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<ellipse class="yefe715tw"/><path class="qpzpo_b1f"/><g class="x8poo_bjf"><ellipse class="t08z06bxh"/><path class="ho69mj0-w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:hole" /></template>

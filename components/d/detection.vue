<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o93lq-byo.css';
import '../../css/a/aimf4ebuf.css';
import '../../css/c/c6vox3all.css';
import '../../css/t/tfpzyrb-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><path clip-rule="evenodd" class="aimf4ebuf"/><path class="c6vox3all"/><path class="tfpzyrb-p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:detection" /></template>

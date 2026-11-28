<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7gtn7bcd.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/k/kat2uhbgv.css';
import '../../css/f/falxvzb7e.css';
import '../../css/k/k6pxfgb5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary x7gtn7bcd"/><g class="dt0cm9dhy primary"><path class="kat2uhbgv"/><path class="falxvzb7e"/><path class="k6pxfgb5x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:acorn-duo" /></template>

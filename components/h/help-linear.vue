<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/s/shu3xdl9q.css';
import '../../css/a/aqhok2bbj.css';
import '../../css/m/mxpc0lbwc.css';
import '../../css/x/xo0gn7bpl.css';
import '../../css/m/mho4m-bvk.css';
import '../../css/y/ynqplacsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="shu3xdl9q"/><circle class="aqhok2bbj"/><path class="mxpc0lbwc"/><path class="xo0gn7bpl"/><path class="mho4m-bvk"/><path class="ynqplacsi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:help-linear" /></template>

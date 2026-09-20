<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/om86e5bdk.css';
import '../../css/v/vfhujpbju.css';
import '../../css/j/jfd0h_bdk.css';
import '../../css/h/hhhzdkbwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="om86e5bdk"/><path class="vfhujpbju"/><path class="jfd0h_bdk"/><path class="hhhzdkbwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:hack" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mkxq1_v_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="mkxq1_v_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-layout-border-horizontal-border-cell-center-format-formatting" /></template>

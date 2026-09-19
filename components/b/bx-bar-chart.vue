<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xhj1p2osp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xhj1p2osp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-bar-chart" /></template>

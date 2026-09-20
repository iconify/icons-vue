<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/he3ym7_zj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="he3ym7_zj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:crosshair-square" /></template>

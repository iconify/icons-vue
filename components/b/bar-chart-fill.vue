<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/re-st0z3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="re-st0z3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bar-chart-fill" /></template>

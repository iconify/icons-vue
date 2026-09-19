<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mv7hfmb3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mv7hfmb3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-pie-chart-alt-2" /></template>

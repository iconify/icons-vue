<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/baahp-79z.css';
import '../../css/h/h55kfl3ha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="baahp-79z"/><path class="h55kfl3ha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-bar-chart-square" /></template>

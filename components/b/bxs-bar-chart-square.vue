<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vulswo0yr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vulswo0yr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-bar-chart-square" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/clk1bdckm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="clk1bdckm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:caret-down" /></template>

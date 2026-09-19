<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfzqp5zje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yfzqp5zje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-squarespace" /></template>

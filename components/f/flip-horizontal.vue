<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-q82zjom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m-q82zjom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:flip-horizontal" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rk31ljb9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rk31ljb9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-zoom" /></template>

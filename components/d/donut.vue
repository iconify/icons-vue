<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0lr8ub9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i0lr8ub9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:donut" /></template>

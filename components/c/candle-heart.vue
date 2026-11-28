<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxeuf6tsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oxeuf6tsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:candle-heart" /></template>

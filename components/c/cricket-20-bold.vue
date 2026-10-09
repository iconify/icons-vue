<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mlx0ax7hq.css';
import '../../css/p/pgcgrcc8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mlx0ax7hq"/><path class="pgcgrcc8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cricket-20-bold" /></template>

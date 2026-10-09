<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q97zhzb7g.css';
import '../../css/v/v361qqj9p.css';
import '../../css/u/ufgiultbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="q97zhzb7g"/><path class="v361qqj9p"/><path class="ufgiultbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:goal-20-bold" /></template>

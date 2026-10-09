<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/syjjg5boi.css';
import '../../css/q/qb-anoa-e.css';
import '../../css/l/l4lb-ym4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="syjjg5boi"/><path class="qb-anoa-e"/><path class="l4lb-ym4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bell-tent-20-bold" /></template>

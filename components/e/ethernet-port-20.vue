<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tv5yvyzmk.css';
import '../../css/y/y6o6t-piu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tv5yvyzmk"/><path class="y6o6t-piu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ethernet-port-20" /></template>

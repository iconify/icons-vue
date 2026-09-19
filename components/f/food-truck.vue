<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cel9776qd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cel9776qd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:food-truck" /></template>

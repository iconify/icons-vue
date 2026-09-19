<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xf1p5q8zl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xf1p5q8zl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:fire-dash" /></template>

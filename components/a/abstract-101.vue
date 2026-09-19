<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zkh_v5bwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zkh_v5bwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-101" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i5eqc1sie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i5eqc1sie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bull-horns" /></template>

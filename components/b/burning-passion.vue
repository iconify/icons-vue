<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j0nr4c1qa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j0nr4c1qa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:burning-passion" /></template>

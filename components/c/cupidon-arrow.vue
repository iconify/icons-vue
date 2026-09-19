<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ff-4-q9jj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ff-4-q9jj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:cupidon-arrow" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfvf0pz8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cfvf0pz8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:furnace" /></template>

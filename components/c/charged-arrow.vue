<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9z8qybkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s9z8qybkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:charged-arrow" /></template>

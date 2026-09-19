<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9z-6laaa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x9z-6laaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:liquid-soap" /></template>

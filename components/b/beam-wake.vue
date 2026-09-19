<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ci8gprbly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ci8gprbly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:beam-wake" /></template>

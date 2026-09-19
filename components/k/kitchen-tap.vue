<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tilsz0f6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tilsz0f6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:kitchen-tap" /></template>

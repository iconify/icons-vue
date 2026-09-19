<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/va4l_-boi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="va4l_-boi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-051" /></template>

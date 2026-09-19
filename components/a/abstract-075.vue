<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sk5v4w-nd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sk5v4w-nd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-075" /></template>

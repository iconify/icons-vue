<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cwi7vl9tb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cwi7vl9tb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-025" /></template>

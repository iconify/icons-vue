<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7hfdzbfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c7hfdzbfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:diamond-hilt" /></template>

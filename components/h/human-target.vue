<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dcq8tkbps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dcq8tkbps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:human-target" /></template>

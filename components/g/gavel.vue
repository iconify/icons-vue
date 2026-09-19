<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drm9wrbrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="drm9wrbrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:gavel" /></template>

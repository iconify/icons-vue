<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lvtxacs1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lvtxacs1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:leg-armor" /></template>

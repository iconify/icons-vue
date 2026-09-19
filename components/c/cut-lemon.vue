<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5xktfb5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d5xktfb5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:cut-lemon" /></template>

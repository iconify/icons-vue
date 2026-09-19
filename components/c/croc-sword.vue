<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vp1c67b8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vp1c67b8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:croc-sword" /></template>

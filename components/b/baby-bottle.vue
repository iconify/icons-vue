<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1zlqhbif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y1zlqhbif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:baby-bottle" /></template>

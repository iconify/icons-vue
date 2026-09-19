<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dyti6_y5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dyti6_y5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:airplane-arrival" /></template>

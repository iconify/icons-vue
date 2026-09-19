<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mlvzy9bfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mlvzy9bfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:checkbox-tree" /></template>

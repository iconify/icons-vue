<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/haaod9unz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="haaod9unz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:card-7-diamonds" /></template>

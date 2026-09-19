<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hl39_obla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hl39_obla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:light-backpack" /></template>

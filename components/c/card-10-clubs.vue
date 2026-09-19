<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lyl_5zpad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lyl_5zpad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:card-10-clubs" /></template>

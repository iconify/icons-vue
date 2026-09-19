<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yda_7p-6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yda_7p-6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:card-draw" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s1y_t1x2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s1y_t1x2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:calculator" /></template>

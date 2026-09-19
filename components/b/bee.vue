<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fl_51bbzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fl_51bbzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bee" /></template>

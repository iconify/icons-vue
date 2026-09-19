<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4zex4brr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e4zex4brr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:kaleidoscope-pearls" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ikpt8rj5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ikpt8rj5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:armor-blueprint" /></template>

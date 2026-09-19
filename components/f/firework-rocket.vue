<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eb7rhof2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eb7rhof2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:firework-rocket" /></template>

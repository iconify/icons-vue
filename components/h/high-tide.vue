<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ieo3-je4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ieo3-je4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:high-tide" /></template>

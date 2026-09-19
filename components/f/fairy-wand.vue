<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qzt069cym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qzt069cym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:fairy-wand" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jvjdxgl3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jvjdxgl3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:branch-arrow" /></template>

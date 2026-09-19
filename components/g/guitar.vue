<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jw8xe0b3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jw8xe0b3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:guitar" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h50f4zr4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h50f4zr4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:diamond-ring" /></template>

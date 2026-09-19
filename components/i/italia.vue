<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-jl-jb7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h-jl-jb7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:italia" /></template>

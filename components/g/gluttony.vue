<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/moq0sj2-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="moq0sj2-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:gluttony" /></template>

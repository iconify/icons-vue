<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jf6liccig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jf6liccig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:crowned-heart" /></template>

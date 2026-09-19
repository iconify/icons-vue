<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0k9_tb0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f0k9_tb0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:book-storm" /></template>

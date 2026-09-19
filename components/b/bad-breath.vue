<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ridum6bct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ridum6bct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bad-breath" /></template>

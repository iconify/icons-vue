<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fiue2_bzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fiue2_bzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:digital-trace" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_icehmzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f_icehmzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:doubled" /></template>

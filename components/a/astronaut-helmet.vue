<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p5hfy99ya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p5hfy99ya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:astronaut-helmet" /></template>

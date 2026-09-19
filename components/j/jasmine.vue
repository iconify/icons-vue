<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fz7qn2b3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fz7qn2b3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:jasmine" /></template>

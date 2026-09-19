<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofixg3wqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ofixg3wqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:glass-celebration" /></template>

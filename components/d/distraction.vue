<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jlr1xxbrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jlr1xxbrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:distraction" /></template>

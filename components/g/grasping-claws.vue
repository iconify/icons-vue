<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfe2s8iii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jfe2s8iii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:grasping-claws" /></template>

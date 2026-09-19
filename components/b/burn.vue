<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j46087b9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j46087b9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:burn" /></template>

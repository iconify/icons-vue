<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohx_6lg8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ohx_6lg8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:forest-entrance" /></template>

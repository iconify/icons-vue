<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ow_br49or.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ow_br49or"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:factory" /></template>

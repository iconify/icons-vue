<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ou22gibla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ou22gibla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:fruit-tree" /></template>

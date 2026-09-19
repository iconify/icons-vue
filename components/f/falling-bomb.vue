<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rez96qejz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rez96qejz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:falling-bomb" /></template>

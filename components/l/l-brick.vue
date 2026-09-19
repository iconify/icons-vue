<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukr9nibmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ukr9nibmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:l-brick" /></template>

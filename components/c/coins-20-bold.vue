<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlxpyqbgk.css';
import '../../css/u/umey9qmui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vlxpyqbgk"/><path class="umey9qmui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:coins-20-bold" /></template>

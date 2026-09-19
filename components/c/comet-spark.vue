<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7xk1o6al.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u7xk1o6al"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:comet-spark" /></template>

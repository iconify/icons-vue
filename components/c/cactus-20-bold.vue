<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1of7cc9l.css';
import '../../css/b/bw6ycksak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w1of7cc9l"/><path class="bw6ycksak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cactus-20-bold" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_0p5kbqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o_0p5kbqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:boxing-glove-surprise" /></template>

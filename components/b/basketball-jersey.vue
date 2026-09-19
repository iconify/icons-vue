<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zr4g3w4iu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zr4g3w4iu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:basketball-jersey" /></template>

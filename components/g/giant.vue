<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zkky4_b_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zkky4_b_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:giant" /></template>

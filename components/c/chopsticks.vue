<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v819-jb_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v819-jb_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:chopsticks" /></template>

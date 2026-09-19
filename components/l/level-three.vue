<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nd4m75byq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nd4m75byq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:level-three" /></template>

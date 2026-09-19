<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t01p27bzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t01p27bzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:fossil" /></template>

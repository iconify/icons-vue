<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j3u9lnadn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j3u9lnadn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:dripping-stone" /></template>

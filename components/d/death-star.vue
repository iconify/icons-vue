<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rr7ginidu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rr7ginidu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:death-star" /></template>

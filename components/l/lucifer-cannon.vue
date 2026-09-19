<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ysuffg60n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ysuffg60n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:lucifer-cannon" /></template>

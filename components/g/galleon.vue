<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nn8yi_w7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nn8yi_w7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:galleon" /></template>

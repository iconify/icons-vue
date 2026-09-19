<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pb_y__bve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pb_y__bve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:card-10-spades" /></template>

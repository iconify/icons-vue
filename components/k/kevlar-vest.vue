<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hlfx1wn9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hlfx1wn9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:kevlar-vest" /></template>

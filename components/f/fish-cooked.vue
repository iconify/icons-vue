<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nk980mb0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nk980mb0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:fish-cooked" /></template>

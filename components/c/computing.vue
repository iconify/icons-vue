<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxgs2dblr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xxgs2dblr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:computing" /></template>

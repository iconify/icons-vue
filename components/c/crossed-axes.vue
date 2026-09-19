<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-_uw5b6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r-_uw5b6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:crossed-axes" /></template>

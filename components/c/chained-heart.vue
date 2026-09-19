<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ii_o8fy9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ii_o8fy9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:chained-heart" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g68wk6bgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g68wk6bgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:funnel" /></template>

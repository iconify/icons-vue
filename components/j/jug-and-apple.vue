<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6teu4bot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="u6teu4bot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:jug-and-apple" /></template>

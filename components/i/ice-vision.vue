<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tg5au16ih.css';
import '../../css/m/mrndicbcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tg5au16ih"/><path class="mrndicbcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ice-vision" /></template>

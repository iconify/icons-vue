<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/znj2yjbcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="znj2yjbcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bookshelf" /></template>

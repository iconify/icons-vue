<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ko-4xac8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ko-4xac8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:life-in-the-balance" /></template>

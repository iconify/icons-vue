<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j2stk6dwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j2stk6dwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-060" /></template>

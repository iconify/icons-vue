<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c26h3kbwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="c26h3kbwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:chat" /></template>

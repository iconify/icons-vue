<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7jgdjm3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="q7jgdjm3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:forward-fast" /></template>

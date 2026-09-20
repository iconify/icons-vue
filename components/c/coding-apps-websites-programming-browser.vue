<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwd16lvwe.css';
import '../../css/a/a7b1h8b_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bwd16lvwe"/><path class="a7b1h8b_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:coding-apps-websites-programming-browser" /></template>

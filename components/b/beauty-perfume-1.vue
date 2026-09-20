<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zyz00n_yo.css';
import '../../css/o/ojcn0pbrl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zyz00n_yo"/><path class="ojcn0pbrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:beauty-perfume-1" /></template>

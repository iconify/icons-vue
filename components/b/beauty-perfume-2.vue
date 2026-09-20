<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c73ylccim.css';
import '../../css/p/pozja0bej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c73ylccim"/><path class="pozja0bej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:beauty-perfume-2" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgpu54aut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wgpu54aut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:fleur-de-lis" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ep1is8b2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ep1is8b2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:data-unreal" /></template>

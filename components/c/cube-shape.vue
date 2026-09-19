<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbuv3ob9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="hbuv3ob9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:cube-shape" /></template>

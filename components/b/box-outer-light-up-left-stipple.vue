<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0ybjnd-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="z0ybjnd-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-outer-light-up-left-stipple" /></template>

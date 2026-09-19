<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ujlo24bpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ujlo24bpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:cursor-arrow-stroke-12" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdzjzu6qb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hdzjzu6qb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:logo-astradb" /></template>

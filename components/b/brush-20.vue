<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t22ym13gb.css';
import '../../css/q/q7uz6xnzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="t22ym13gb"/><path class="q7uz6xnzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:brush-20" /></template>

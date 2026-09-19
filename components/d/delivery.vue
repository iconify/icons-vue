<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzab02bem.css';
import '../../css/r/rl2fx36gi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dzab02bem"/><path class="rl2fx36gi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:delivery" /></template>

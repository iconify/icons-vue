<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ca5ecz53l.css';
import '../../css/r/rrrw2jbhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ca5ecz53l"/><path class="rrrw2jbhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:data-blob" /></template>

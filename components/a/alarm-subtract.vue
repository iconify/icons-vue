<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vsubc8bso.css';
import '../../css/b/b3wbj4but.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vsubc8bso"/><path class="b3wbj4but"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:alarm-subtract" /></template>

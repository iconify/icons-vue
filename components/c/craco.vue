<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9li8s_7q.css';
import '../../css/e/ex0rr4b0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j9li8s_7q"/><path class="ex0rr4b0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:craco" /></template>

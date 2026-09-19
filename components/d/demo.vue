<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izajwurpr.css';
import '../../css/g/g24buwbsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="izajwurpr"/><path class="g24buwbsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:demo" /></template>

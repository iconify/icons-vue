<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bla2ybb5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bla2ybb5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-consulting-advantage-agent" /></template>

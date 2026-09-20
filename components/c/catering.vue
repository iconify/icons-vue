<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c97p5ln2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="c97p5ln2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:catering" /></template>

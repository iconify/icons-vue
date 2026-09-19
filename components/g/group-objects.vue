<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-a__rbow.css';
import '../../css/l/lppl2sbhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="l-a__rbow"/><path class="lppl2sbhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:group-objects" /></template>

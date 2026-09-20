<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vur7jkzgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vur7jkzgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:landscape2" /></template>

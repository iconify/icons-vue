<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zalphcmjo.css';
import '../../css/f/fqa96gb_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zalphcmjo"/><path class="fqa96gb_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:button-flush-left" /></template>

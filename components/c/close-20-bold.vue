<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ans_9vb2b.css';
import '../../css/a/az1dy05bx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ans_9vb2b"/><path class="az1dy05bx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:close-20-bold" /></template>

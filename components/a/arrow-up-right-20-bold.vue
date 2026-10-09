<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/az1dy05bx.css';
import '../../css/d/d6eot3bqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="az1dy05bx"/><path class="d6eot3bqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrow-up-right-20-bold" /></template>

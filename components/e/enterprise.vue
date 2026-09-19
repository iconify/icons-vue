<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q23s4ccja.css';
import '../../css/m/mn4wyk1sv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q23s4ccja"/><path class="mn4wyk1sv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:enterprise" /></template>

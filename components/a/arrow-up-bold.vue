<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpkwgyn6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="qpkwgyn6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:arrow-up-bold" /></template>

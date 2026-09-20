<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6s9z3b5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="i6s9z3b5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-vertical-right" /></template>

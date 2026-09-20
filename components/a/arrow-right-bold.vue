<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4oi2s2oe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="v4oi2s2oe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:arrow-right-bold" /></template>

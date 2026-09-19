<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uk1hhe5-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="uk1hhe5-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:arrow-up-right-mirrored-8" /></template>

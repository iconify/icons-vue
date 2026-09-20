<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kd5n0mazb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="kd5n0mazb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:alpha-t" /></template>

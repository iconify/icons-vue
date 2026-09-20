<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nlvp0pbyy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="nlvp0pbyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-outer-light-up-right-stipple" /></template>

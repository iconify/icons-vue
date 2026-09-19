<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7vnzccas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1280,"height":1536};
const content = `<path class="u7vnzccas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:bookmark" /></template>

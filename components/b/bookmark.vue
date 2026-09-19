<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6tr8sb3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g6tr8sb3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:bookmark" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o57ysrbfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="o57ysrbfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:drop-outline" /></template>

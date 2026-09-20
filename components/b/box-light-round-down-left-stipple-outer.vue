<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2-khbbac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="q2-khbbac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-round-down-left-stipple-outer" /></template>

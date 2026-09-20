<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rb-fjmb1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="rb-fjmb1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-outer-light-up-vertical-stipple-right" /></template>

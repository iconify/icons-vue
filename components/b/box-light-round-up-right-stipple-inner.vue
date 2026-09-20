<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jxix1zkta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="jxix1zkta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-round-up-right-stipple-inner" /></template>

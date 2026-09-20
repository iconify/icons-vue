<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxy8lcb5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="oxy8lcb5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-double-vertical-light-right" /></template>

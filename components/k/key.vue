<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yc1d4tesh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="yc1d4tesh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:key" /></template>

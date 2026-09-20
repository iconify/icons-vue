<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlkgi9b-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="vlkgi9b-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:chevron-right" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vl3c13s6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="vl3c13s6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:alpha-r-fill" /></template>

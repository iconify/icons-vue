<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w0tdrhhdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="w0tdrhhdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:alpha-x" /></template>

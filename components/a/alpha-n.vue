<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-9b11ecn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="x-9b11ecn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:alpha-n" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oocfn2e4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="oocfn2e4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:alpha-h-fill" /></template>

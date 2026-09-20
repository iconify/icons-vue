<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h0gygpb-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="h0gygpb-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-fold-up-right" /></template>

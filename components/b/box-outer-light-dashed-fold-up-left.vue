<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6r2qubzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="d6r2qubzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-outer-light-dashed-fold-up-left" /></template>

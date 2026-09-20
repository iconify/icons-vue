<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jl42bbbnp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="jl42bbbnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:arrow-left-up" /></template>

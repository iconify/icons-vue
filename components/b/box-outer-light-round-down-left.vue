<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ci5p-rb7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="ci5p-rb7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-outer-light-round-down-left" /></template>

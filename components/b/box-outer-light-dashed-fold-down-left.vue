<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r4ds2m-5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="r4ds2m-5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-outer-light-dashed-fold-down-left" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pn8bvackf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="pn8bvackf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:chevron-left-circle" /></template>

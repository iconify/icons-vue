<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e634_5b5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="e634_5b5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-fold-down-right" /></template>

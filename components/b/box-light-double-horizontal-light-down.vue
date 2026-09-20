<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aja--_w3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="aja--_w3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-double-horizontal-light-down" /></template>

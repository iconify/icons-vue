<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e1m-wck-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="e1m-wck-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:cube-shape-solid" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbj_pyy4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="mbj_pyy4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:bookmark" /></template>

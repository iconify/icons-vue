<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzt9c_6gx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="lzt9c_6gx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:chart-bar" /></template>

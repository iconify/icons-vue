<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sa2kh1q4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="sa2kh1q4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-double-horizontal" /></template>

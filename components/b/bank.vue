<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jonzy7b1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="jonzy7b1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:bank" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fkc41lb-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="fkc41lb-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:alpha-v" /></template>

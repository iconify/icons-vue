<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i064ubcxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="i064ubcxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:alpha-t-fill" /></template>

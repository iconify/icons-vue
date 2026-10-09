<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hf8qgfbqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hf8qgfbqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cloud-48" /></template>

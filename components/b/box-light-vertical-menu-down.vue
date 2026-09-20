<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/es3w6ybnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="es3w6ybnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-vertical-menu-down" /></template>

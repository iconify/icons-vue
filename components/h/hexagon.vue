<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jds-7weev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="jds-7weev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:hexagon" /></template>

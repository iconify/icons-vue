<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a7a0dzb4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="a7a0dzb4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:door-open" /></template>

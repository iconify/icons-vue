<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eam5p6x4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="eam5p6x4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:alpha-a-fill" /></template>

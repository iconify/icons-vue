<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ih7wd8-4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="ih7wd8-4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:alpha-c-fill" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sk0zolb2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":40,"height":40};
const content = `<path class="sk0zolb2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iwwa:chart-style2" /></template>

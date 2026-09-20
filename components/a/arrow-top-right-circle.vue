<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gspte2b7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="gspte2b7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:arrow-top-right-circle" /></template>

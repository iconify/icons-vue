<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/py5kzrbnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="py5kzrbnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:bar-chart-fill-12" /></template>

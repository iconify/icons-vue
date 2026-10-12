<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/joiq4kbkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="joiq4kbkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:bar-chart-fill-20" /></template>

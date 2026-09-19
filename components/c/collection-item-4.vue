<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dr56h3nhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":480};
const content = `<path class="dr56h3nhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:collection-item-4" /></template>

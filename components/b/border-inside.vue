<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ta-gi97mi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="ta-gi97mi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:border-inside" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2m1qdbbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="r2m1qdbbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:bicycle-plug" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uw9yn79-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="uw9yn79-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:houseboat" /></template>

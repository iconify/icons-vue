<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/of4ksgw-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="of4ksgw-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:location-fill-16" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s92d9qb-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s92d9qb-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:heat-map-03" /></template>

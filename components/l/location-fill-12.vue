<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u4y1kvb4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="u4y1kvb4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:location-fill-12" /></template>

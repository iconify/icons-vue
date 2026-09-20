<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsi6l9whp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dsi6l9whp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:aerial-cargo-lift" /></template>

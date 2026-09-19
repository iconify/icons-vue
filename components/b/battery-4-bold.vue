<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4e0i62as.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="v4e0i62as"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:battery-4-bold" /></template>

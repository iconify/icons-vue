<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yprrdym3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="yprrdym3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bear-spray-can-with-spray-and-recycling-symbol" /></template>

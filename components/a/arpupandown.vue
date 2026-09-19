<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bigywb2mm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="bigywb2mm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:arpupandown" /></template>

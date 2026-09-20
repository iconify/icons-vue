<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-nsxabpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r-nsxabpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-skull-1" /></template>

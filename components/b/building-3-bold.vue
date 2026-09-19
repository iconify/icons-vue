<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rsx8atb8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="rsx8atb8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:building-3-bold" /></template>

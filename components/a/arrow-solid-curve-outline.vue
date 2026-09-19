<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9yv_e71e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="g9yv_e71e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:arrow-solid-curve-outline" /></template>

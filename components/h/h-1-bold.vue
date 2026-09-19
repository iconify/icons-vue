<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rh8bllbeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="rh8bllbeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:h-1-bold" /></template>

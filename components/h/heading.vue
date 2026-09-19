<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ab7bv8b0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="ab7bv8b0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:heading" /></template>

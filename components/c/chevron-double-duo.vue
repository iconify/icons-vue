<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygufz_b9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="ygufz_b9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:chevron-double-duo" /></template>

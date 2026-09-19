<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j72wdcj5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="j72wdcj5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:code-outline" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eyllv6izc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="eyllv6izc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:crop-outline" /></template>

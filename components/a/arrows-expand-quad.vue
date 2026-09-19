<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2u5f7bvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="s2u5f7bvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:arrows-expand-quad" /></template>

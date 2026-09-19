<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2f5-g1mk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="z2f5-g1mk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:docs-1-bold" /></template>

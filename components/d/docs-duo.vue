<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ziptyqb_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="ziptyqb_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:docs-duo" /></template>

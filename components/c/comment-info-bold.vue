<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zx2qfgb3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="zx2qfgb3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:comment-info-bold" /></template>

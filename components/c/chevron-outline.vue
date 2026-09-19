<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdet07bna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="xdet07bna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:chevron-outline" /></template>

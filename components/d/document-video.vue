<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpt8g1b7z.css';
import '../../css/n/nketkfbkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wpt8g1b7z"/><path class="nketkfbkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:document-video" /></template>

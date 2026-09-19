<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgv7ttrgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="xgv7ttrgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:baseball-bold" /></template>

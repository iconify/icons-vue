<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vl_3njf8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="vl_3njf8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:four-outline" /></template>

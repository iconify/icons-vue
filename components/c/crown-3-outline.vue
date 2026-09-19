<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1r-0chkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="y1r-0chkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:crown-3-outline" /></template>

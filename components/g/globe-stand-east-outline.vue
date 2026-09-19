<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_j5ambxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="y_j5ambxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:globe-stand-east-outline" /></template>

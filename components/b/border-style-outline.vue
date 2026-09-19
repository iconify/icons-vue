<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a4wf3lb-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="a4wf3lb-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:border-style-outline" /></template>

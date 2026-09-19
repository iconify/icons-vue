<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qab7_jb8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="qab7_jb8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:die-1-bold" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4gc-vbgr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="g4gc-vbgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:heading-duo" /></template>

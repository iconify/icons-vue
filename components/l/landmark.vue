<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2hxlccii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="d2hxlccii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:landmark" /></template>

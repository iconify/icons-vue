<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jttibe98e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="jttibe98e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:arrow-line-start-outline" /></template>

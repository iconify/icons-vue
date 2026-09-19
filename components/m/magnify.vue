<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/elkmmg68c.css';
import '../../css/y/y3-1k1brf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs/><path class="elkmmg68c"/><path class="y3-1k1brf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:magnify" /></template>

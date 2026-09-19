<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-xbwlbyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="u-xbwlbyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:caret-hollow" /></template>

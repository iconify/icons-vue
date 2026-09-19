<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t1cf7r2zc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="t1cf7r2zc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:calendar-outline" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_-xccbdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="s_-xccbdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:arrows-compress-duo" /></template>

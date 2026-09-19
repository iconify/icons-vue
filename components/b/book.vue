<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xg9lrzmst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="xg9lrzmst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:book" /></template>

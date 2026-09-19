<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aoeo9--2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="aoeo9--2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:h-3-duo" /></template>

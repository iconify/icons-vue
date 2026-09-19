<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ay90zkbwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="ay90zkbwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:border-none" /></template>

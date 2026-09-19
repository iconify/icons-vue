<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mllqukd8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="mllqukd8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:equals-bold" /></template>

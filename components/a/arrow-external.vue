<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5_5wi6ae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="x5_5wi6ae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:arrow-external" /></template>

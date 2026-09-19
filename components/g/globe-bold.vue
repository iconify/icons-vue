<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jv-c2w6li.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="jv-c2w6li"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:globe-bold" /></template>

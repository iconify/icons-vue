<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqm8r7dhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="oqm8r7dhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:italic" /></template>

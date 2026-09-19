<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sy12u3bhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="sy12u3bhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:chart-bar" /></template>

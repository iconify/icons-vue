<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdyrk5blc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="bdyrk5blc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:chart-pie-bold" /></template>

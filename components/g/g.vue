<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2do5-bxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="l2do5-bxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:g" /></template>

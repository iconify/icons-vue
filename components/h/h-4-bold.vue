<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/or95d4b4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="or95d4b4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:h-4-bold" /></template>

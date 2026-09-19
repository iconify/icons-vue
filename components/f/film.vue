<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o2etqnbnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="o2etqnbnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:film" /></template>

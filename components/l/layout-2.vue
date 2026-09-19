<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_k4d2ull.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="q_k4d2ull"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:layout-2" /></template>

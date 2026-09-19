<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhqi1ub4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="vhqi1ub4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:line-duo" /></template>

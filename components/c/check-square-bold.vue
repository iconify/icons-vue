<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sqt3tyb-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="sqt3tyb-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:check-square-bold" /></template>

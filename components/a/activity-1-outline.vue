<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a33rtejtl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="a33rtejtl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:activity-1-outline" /></template>

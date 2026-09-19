<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0v9gt2dh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="o0v9gt2dh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:activity-outline" /></template>

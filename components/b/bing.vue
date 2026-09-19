<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gr___x8pl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":464,"height":456};
const content = `<path class="gr___x8pl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:bing" /></template>

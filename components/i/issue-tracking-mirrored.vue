<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1732fy7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="m1732fy7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:issue-tracking-mirrored" /></template>

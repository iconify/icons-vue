<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tz_ni_bcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tz_ni_bcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:derelict-house" /></template>

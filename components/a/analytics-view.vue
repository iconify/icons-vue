<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yiwwxsc_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="yiwwxsc_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:analytics-view" /></template>

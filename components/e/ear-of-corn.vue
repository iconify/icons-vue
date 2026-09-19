<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ace0o87kt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ace0o87kt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:ear-of-corn" /></template>

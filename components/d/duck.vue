<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wfz99bcbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wfz99bcbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:duck" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/euga36bjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="euga36bjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:end" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aqh-e-b9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="aqh-e-b9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:card-index-dividers" /></template>

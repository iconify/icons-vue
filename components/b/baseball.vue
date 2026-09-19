<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxu8d89-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nxu8d89-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:baseball" /></template>

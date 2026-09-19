<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbdz0v2ph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path clip-rule="evenodd" class="rbdz0v2ph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:curly-loop" /></template>

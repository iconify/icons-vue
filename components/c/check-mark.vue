<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q39_z9bzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path clip-rule="evenodd" class="q39_z9bzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:check-mark" /></template>

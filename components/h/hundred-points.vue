<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygp9ilbci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path clip-rule="evenodd" class="ygp9ilbci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:hundred-points" /></template>

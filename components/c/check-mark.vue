<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0_j9xhzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path clip-rule="evenodd" class="d0_j9xhzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:check-mark" /></template>

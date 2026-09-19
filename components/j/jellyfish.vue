<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3j32evkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path clip-rule="evenodd" class="d3j32evkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:jellyfish" /></template>

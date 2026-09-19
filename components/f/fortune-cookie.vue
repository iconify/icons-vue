<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhy-nmuzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nhy-nmuzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:fortune-cookie" /></template>

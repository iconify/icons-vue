<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-db58byd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o-db58byd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:clapping-hands" /></template>

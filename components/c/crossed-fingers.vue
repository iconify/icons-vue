<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xretw0lyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xretw0lyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:crossed-fingers" /></template>

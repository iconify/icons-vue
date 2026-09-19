<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aidrj0qgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="aidrj0qgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:droplet" /></template>

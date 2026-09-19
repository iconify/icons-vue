<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6e8x6blc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="b6e8x6blc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:ice-hockey" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwoq-nw4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bwoq-nw4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:aquarius" /></template>

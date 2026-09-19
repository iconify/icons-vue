<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zetk6vb3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zetk6vb3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:cricket-game" /></template>

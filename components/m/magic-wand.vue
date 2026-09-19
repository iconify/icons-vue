<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/livo-ebhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="livo-ebhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:magic-wand" /></template>

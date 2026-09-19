<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/malb5obyq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="malb5obyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:film-frames" /></template>

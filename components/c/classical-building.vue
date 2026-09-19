<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/modq4lqgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="modq4lqgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:classical-building" /></template>

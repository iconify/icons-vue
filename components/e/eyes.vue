<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4d115tme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="z4d115tme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:eyes" /></template>

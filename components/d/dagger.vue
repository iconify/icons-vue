<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0c0xbc1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n0c0xbc1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:dagger" /></template>

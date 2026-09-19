<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfux_ebdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kfux_ebdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:crossed-flags" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jj7e9omtg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jj7e9omtg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:chair" /></template>

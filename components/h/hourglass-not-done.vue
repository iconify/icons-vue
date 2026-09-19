<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dk0ng_hoo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dk0ng_hoo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:hourglass-not-done" /></template>

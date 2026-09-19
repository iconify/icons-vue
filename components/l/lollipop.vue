<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ov13c6xvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ov13c6xvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:lollipop" /></template>

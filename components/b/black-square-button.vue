<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wsfengbia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wsfengbia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:black-square-button" /></template>

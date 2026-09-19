<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/echedebgr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="echedebgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:briefcase" /></template>

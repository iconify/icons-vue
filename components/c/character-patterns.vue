<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dimqj2ncr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dimqj2ncr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:character-patterns" /></template>

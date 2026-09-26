<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/arf40vqct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="arf40vqct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:content-navigator-sync-paused" /></template>

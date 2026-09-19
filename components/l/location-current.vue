<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/esl1noc6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="esl1noc6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:location-current" /></template>

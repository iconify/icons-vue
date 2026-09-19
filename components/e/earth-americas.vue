<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ie1a0_6jd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ie1a0_6jd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:earth-americas" /></template>

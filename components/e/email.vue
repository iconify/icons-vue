<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6cgipokr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i6cgipokr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:email" /></template>

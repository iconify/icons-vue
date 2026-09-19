<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s78jxz9te.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s78jxz9te"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:c" /></template>

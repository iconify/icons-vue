<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nzfwk9bhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nzfwk9bhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:direction-rotary-straight" /></template>

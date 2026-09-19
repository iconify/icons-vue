<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cy5ym81zr.css';
import '../../css/z/z8k-y_stg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cy5ym81zr"/><path class="z8k-y_stg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:dns-services" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxjmxtpcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bxjmxtpcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:caret-sort-down" /></template>

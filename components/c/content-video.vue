<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eufwep-yh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="eufwep-yh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:content-video" /></template>

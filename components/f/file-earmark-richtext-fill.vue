<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmx57fb3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cmx57fb3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:file-earmark-richtext-fill" /></template>

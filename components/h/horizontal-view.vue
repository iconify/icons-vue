<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-icr-r2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s-icr-r2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:horizontal-view" /></template>

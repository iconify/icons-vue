<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilpt9acqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ilpt9acqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:letter-qq" /></template>

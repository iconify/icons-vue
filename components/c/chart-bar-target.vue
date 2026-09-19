<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r6u3nob_e.css';
import '../../css/c/cc3ew4s6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r6u3nob_e"/><path class="cc3ew4s6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:chart-bar-target" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vnz2qsb9e.css';
import '../../css/j/j8yh1x58g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vnz2qsb9e"/><path class="j8yh1x58g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:gateway-public" /></template>

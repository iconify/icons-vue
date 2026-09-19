<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m4t-l8b1f.css';
import '../../css/e/ew86px5aw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="m4t-l8b1f"/><path class="ew86px5aw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:diagram" /></template>

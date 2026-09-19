<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jvrpqcbxs.css';
import '../../css/m/m025-fvbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jvrpqcbxs"/><path class="m025-fvbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:connection-signal" /></template>

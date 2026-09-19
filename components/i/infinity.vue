<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ocx9jvbhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ocx9jvbhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:infinity" /></template>

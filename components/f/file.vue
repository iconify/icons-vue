<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j2ew5t0wm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":344,"height":432};
const content = `<path class="j2ew5t0wm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:file" /></template>

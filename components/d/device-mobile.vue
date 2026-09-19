<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4dcppbne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l4dcppbne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:device-mobile" /></template>

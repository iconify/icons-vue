<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vu5cfjbnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":256};
const content = `<path class="vu5cfjbnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:digital-dot" /></template>

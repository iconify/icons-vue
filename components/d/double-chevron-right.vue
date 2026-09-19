<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkt748d0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lkt748d0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:double-chevron-right" /></template>

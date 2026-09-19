<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tppfsxdkc.css';
import '../../css/d/dosysb90i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tppfsxdkc"/><path class="dosysb90i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:logo-vue" /></template>

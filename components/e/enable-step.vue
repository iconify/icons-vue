<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrqw_eyts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qrqw_eyts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:enable-step" /></template>

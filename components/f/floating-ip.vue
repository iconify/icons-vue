<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o39udobwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o39udobwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:floating-ip" /></template>

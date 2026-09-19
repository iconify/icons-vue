<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n87947b0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n87947b0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:eyedropper" /></template>

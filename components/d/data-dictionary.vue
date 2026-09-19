<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/va3b78biq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="va3b78biq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:data-dictionary" /></template>

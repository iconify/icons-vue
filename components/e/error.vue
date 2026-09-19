<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hjp4ez7iq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="hjp4ez7iq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:error" /></template>

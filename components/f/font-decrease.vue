<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mz2w0xb6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="mz2w0xb6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:font-decrease" /></template>

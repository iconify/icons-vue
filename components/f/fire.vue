<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/svf39sb5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="svf39sb5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:fire" /></template>

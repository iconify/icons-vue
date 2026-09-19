<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pcx4prbjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pcx4prbjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:logo-linkedin" /></template>

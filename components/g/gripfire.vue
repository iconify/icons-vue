<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0soejf-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q0soejf-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:gripfire" /></template>

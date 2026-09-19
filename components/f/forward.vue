<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7avmm_pz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="s7avmm_pz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:forward" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6_s7g3ed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="q6_s7g3ed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:align-full-width" /></template>

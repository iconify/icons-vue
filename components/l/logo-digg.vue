<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oa35v-cta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="oa35v-cta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:logo-digg" /></template>

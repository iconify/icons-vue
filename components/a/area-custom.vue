<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sypmpob3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sypmpob3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:area-custom" /></template>

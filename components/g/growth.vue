<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gosld0u7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gosld0u7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:growth" /></template>

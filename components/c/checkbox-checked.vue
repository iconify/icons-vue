<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2nbqq6me.css';
import '../../css/k/k2czn9xff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="w2nbqq6me"/><path class="k2czn9xff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:checkbox-checked" /></template>

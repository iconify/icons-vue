<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/euw05tbjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="euw05tbjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:circle" /></template>

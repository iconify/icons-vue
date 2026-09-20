<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/glr4g87vl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="glr4g87vl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:budded-latin-cross" /></template>

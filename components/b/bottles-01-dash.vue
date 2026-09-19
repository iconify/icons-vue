<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4bbxcc8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o4bbxcc8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:bottles-01-dash" /></template>

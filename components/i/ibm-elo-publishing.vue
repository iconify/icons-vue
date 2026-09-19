<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqdqqi13i.css';
import '../../css/a/a3y0hhb5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="eqdqqi13i"/><path class="a3y0hhb5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-elo-publishing" /></template>

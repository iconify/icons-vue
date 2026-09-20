<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h4el2bbpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h4el2bbpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:helmet-safety-filled" /></template>

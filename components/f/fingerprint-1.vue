<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zo-_1ub0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="zo-_1ub0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:fingerprint-1" /></template>

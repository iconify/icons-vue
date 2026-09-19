<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mpalt4_oj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mpalt4_oj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:asana" /></template>

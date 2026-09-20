<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkf7gnbzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="kkf7gnbzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:gsm4" /></template>

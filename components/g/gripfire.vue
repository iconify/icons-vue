<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqcjrk-gv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="vqcjrk-gv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:gripfire" /></template>

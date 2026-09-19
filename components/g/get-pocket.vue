<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7_s0d79d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="e7_s0d79d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:get-pocket" /></template>

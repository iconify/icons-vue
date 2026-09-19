<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x0_tc6b1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="x0_tc6b1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:coqui" /></template>

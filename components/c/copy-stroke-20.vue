<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mx0i85btj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mx0i85btj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:copy-stroke-20" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m06b_wb2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":63,"height":64};
const content = `<path class="m06b_wb2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:i-information-us" /></template>

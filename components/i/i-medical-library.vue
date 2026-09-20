<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lked-oz3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="lked-oz3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:i-medical-library" /></template>

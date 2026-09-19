<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzffr4fxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zzffr4fxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:logo-capacitor" /></template>

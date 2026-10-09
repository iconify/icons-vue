<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dbl65ebhc.css';
import '../../css/o/opemywb2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dbl65ebhc"/><path class="opemywb2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bed-20-bold" /></template>

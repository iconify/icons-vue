<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v8mjr5bmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="v8mjr5bmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:cloud" /></template>

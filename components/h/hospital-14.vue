<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iuaa2cbji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="iuaa2cbji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:hospital-14" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khre3_bur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="khre3_bur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:expeditedssl" /></template>

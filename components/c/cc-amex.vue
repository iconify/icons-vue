<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l05o_pbdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="l05o_pbdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:cc-amex" /></template>

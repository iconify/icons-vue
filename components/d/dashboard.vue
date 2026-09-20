<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rtv5yrb6k.css';
import '../../css/s/stxf-nbvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="rtv5yrb6k"/><path class="stxf-nbvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:dashboard" /></template>

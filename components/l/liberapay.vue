<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4xbjs1xt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="w4xbjs1xt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:liberapay" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4rf-acxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="q4rf-acxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:btc" /></template>

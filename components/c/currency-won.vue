<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mw4g2xfsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mw4g2xfsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:currency-won" /></template>

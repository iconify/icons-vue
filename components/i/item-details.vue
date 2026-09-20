<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hjfxb6cvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hjfxb6cvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:item-details" /></template>

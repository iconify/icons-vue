<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ub10_dwjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="ub10_dwjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:conversation" /></template>

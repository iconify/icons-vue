<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/caf4w40kg.css';
import '../../css/v/vqmcn9mpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="caf4w40kg"/><path class="vqmcn9mpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:function-argument-ltr" /></template>

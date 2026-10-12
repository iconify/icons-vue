<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3s1yw0am.css';
import '../../css/h/h0u2-1bxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="y3s1yw0am"/><path class="h0u2-1bxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:cloud-arrow-up-stroke-20" /></template>

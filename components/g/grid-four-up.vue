<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqvr593jz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="hqvr593jz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:grid-four-up" /></template>

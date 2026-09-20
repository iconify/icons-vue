<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fe6_i0b_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fe6_i0b_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:gmail-solid" /></template>

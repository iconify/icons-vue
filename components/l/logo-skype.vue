<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5aom4pxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f5aom4pxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:logo-skype" /></template>

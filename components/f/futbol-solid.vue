<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8-diacjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f8-diacjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:futbol-solid" /></template>

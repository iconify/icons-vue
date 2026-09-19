<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjjko4g0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="fjjko4g0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:alipay" /></template>

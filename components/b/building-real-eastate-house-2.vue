<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zz01e0bkd.css';
import '../../css/m/mmrm4kbcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zz01e0bkd"/><path class="mmrm4kbcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:building-real-eastate-house-2" /></template>

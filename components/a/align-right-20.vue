<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvt-qjbrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cvt-qjbrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:align-right-20" /></template>

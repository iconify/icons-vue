<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grrp81bcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="grrp81bcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:life-ring" /></template>

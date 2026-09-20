<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/idkbi6nqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="idkbi6nqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-loading-50-percent" /></template>

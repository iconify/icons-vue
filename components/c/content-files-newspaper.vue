<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jkms2ybtu.css';
import '../../css/f/fw-p8rb7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jkms2ybtu"/><path class="fw-p8rb7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:content-files-newspaper" /></template>

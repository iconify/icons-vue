<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmp8_bcja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vmp8_bcja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:hotjar" /></template>

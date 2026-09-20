<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lz2g28hhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="lz2g28hhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:airport-plane" /></template>

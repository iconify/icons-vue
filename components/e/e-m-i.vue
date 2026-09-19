<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sefzsac2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="sefzsac2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:e-m-i" /></template>

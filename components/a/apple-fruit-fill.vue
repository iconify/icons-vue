<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ckv6ibbjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ckv6ibbjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:apple-fruit-fill" /></template>

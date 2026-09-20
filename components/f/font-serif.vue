<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzn6gmbtb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lzn6gmbtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:font-serif" /></template>

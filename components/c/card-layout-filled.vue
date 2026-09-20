<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/co6w5rbbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="co6w5rbbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:card-layout-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mq9r4qbvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mq9r4qbvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:ebay" /></template>

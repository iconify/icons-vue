<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/po1nrc4wh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="po1nrc4wh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:logo-pinterest" /></template>

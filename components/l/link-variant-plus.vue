<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6knleb3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f6knleb3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:link-variant-plus" /></template>

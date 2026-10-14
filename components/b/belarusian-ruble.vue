<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-m5rn9ii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-m5rn9ii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:belarusian-ruble" /></template>

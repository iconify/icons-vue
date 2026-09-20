<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivfm2ebzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ivfm2ebzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:currency-lira-2-fill" /></template>

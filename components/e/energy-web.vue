<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmqol_-wr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kmqol_-wr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:energy-web" /></template>

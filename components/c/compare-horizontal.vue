<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ar1m2gsxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ar1m2gsxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:compare-horizontal" /></template>

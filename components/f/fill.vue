<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eoxo5y0ru.css';
import '../../css/n/nxz2d6bqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eoxo5y0ru"/><path class="nxz2d6bqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:fill" /></template>

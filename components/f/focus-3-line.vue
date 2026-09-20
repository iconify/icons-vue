<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpd_f5y1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jpd_f5y1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:focus-3-line" /></template>

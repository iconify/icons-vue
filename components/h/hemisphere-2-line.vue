<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcn7q4-vh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vcn7q4-vh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hemisphere-2-line" /></template>

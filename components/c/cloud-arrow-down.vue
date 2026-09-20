<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-yi1kzxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-yi1kzxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cloud-arrow-down" /></template>

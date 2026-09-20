<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqscv41wy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fqscv41wy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:battery-2-fill" /></template>

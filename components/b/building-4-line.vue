<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gv666bbhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gv666bbhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:building-4-line" /></template>

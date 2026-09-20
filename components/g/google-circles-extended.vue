<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dpiqj8bhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dpiqj8bhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:google-circles-extended" /></template>

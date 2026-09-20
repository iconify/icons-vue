<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmin66b0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vmin66b0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:corner-up-left-line" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lluzz6bir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lluzz6bir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alphabet-m-circle" /></template>

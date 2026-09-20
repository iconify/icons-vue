<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tf4yk0big.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tf4yk0big"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:file-2-line-2" /></template>

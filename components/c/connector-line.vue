<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dpx_oobfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dpx_oobfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:connector-line" /></template>

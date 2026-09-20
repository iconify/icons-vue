<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxl_0ldls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dxl_0ldls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cloud-snow-fill" /></template>

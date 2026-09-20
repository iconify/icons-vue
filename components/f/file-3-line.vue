<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxfc_g7ok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vxfc_g7ok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:file-3-line" /></template>

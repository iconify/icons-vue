<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dd6awuktp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dd6awuktp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:close" /></template>

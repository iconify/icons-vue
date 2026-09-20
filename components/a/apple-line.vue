<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gddh23byz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gddh23byz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:apple-line" /></template>

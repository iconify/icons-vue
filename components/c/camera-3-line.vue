<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-rtdmbnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w-rtdmbnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:camera-3-line" /></template>

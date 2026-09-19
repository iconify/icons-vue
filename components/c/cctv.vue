<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eg2fy-b0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eg2fy-b0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cctv" /></template>

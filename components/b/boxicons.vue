<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z939fub_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z939fub_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:boxicons" /></template>

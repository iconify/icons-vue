<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/le7_c61zy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="le7_c61zy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:cross" /></template>

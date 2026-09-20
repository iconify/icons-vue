<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ddr_3pbvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ddr_3pbvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:align-justify-fill" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxpld78_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sxpld78_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cursor-fill" /></template>

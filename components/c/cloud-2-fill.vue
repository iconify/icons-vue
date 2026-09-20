<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tsmudmsks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tsmudmsks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cloud-2-fill" /></template>

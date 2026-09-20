<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vj9exkbjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vj9exkbjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:file-excel-2-line" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3-5t2bun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g3-5t2bun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:chart-column-increasing" /></template>

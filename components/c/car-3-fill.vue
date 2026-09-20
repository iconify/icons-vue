<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqsf3pbmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tqsf3pbmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:car-3-fill" /></template>

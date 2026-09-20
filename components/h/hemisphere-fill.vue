<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/na23c-lwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="na23c-lwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hemisphere-fill" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h0dw-9b1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h0dw-9b1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:arrow-up-right-square-solid" /></template>

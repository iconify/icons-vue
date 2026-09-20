<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/es4gnh0fa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="es4gnh0fa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-y-hexagon-solid" /></template>

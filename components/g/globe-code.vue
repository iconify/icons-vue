<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmdt1p3iv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wmdt1p3iv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:globe-code" /></template>

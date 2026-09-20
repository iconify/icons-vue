<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxjrk3bzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uxjrk3bzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:diamond-2-line" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1gbacb4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x1gbacb4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:fahrenheit-fill" /></template>

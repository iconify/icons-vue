<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gj8k4mbbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gj8k4mbbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:circle-half" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ju9d-d0dv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ju9d-d0dv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-bing" /></template>

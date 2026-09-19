<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pthb8fbcv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pthb8fbcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-youtube" /></template>

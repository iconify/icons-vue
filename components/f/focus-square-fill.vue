<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpcs_f_wh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wpcs_f_wh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:focus-square-fill" /></template>

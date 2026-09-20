<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/me7l_yy_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="me7l_yy_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:circle" /></template>

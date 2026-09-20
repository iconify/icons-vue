<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gogw79u_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gogw79u_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-v-hexagon-solid" /></template>

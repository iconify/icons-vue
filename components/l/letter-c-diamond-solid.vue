<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4c7fub3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w4c7fub3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-c-diamond-solid" /></template>

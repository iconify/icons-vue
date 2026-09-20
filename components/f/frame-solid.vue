<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mak4hx3pt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mak4hx3pt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:frame-solid" /></template>

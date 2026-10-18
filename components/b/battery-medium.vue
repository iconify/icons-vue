<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wk4xhy-nc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wk4xhy-nc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:battery-medium" /></template>

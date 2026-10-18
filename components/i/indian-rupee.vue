<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yiji8wbws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yiji8wbws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:indian-rupee" /></template>

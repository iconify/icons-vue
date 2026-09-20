<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hgtdrqegm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hgtdrqegm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:heart" /></template>

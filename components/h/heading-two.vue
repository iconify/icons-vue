<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wlp4ho8vz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wlp4ho8vz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:heading-two" /></template>

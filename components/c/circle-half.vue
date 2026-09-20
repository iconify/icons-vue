<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jf93g32nh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jf93g32nh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:circle-half" /></template>

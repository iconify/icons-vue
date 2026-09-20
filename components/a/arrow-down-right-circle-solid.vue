<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yq3y2-bza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yq3y2-bza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:arrow-down-right-circle-solid" /></template>

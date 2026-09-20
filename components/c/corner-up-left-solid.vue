<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p0_ge5bwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p0_ge5bwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:corner-up-left-solid" /></template>

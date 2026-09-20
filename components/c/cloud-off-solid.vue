<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ogsyzf9pu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ogsyzf9pu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:cloud-off-solid" /></template>

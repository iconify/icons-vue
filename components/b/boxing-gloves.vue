<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ksnh2ccrn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ksnh2ccrn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:boxing-gloves" /></template>

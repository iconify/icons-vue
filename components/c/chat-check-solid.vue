<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jdfs-uwca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jdfs-uwca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chat-check-solid" /></template>

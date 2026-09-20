<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dq1pystjj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dq1pystjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:folder-2-fill" /></template>

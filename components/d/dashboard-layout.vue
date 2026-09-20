<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yym1m5i-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yym1m5i-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:dashboard-layout" /></template>

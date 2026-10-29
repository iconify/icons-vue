<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xg4u5sbfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xg4u5sbfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:arrow-down-left-solid" /></template>

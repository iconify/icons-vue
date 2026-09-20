<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oa1et4hnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oa1et4hnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:drop-fill" /></template>

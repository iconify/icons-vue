<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/av-0zqb-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="av-0zqb-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:arrow-left" /></template>

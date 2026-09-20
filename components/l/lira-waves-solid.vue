<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yaphsqb4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yaphsqb4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:lira-waves-solid" /></template>

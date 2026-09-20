<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uylaye4tc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uylaye4tc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chart-bar" /></template>

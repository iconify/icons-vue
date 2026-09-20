<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukytkrfwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ukytkrfwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:lightbulb-group" /></template>

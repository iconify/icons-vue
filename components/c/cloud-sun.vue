<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fi-r9sb2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fi-r9sb2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:cloud-sun" /></template>

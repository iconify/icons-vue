<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mggrdsrzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mggrdsrzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:fire-extinguisher-filled" /></template>

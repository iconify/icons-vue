<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ueo59ebwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ueo59ebwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:file-list-3-line" /></template>

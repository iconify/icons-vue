<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vm-3dk3di.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vm-3dk3di"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cloud-check-line" /></template>

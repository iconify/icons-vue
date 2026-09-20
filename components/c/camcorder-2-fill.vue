<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozar6vojc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ozar6vojc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:camcorder-2-fill" /></template>

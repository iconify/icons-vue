<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/epgl_be4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="epgl_be4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:dry-line" /></template>

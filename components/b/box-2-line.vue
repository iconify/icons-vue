<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fp3c5t_6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fp3c5t_6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:box-2-line" /></template>

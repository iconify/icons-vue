<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zu0pncc0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zu0pncc0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:drawer-line" /></template>

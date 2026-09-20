<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3b1qfk3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e3b1qfk3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:back-2-line" /></template>

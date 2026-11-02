<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ll-_dkb7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ll-_dkb7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:dashboard-2-line" /></template>

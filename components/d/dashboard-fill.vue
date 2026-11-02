<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vt7hbcc_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vt7hbcc_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:dashboard-fill" /></template>

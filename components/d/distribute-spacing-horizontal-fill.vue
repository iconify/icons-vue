<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p0in5lbks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p0in5lbks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:distribute-spacing-horizontal-fill" /></template>

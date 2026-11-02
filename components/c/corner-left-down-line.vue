<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivq7ni1-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ivq7ni1-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:corner-left-down-line" /></template>

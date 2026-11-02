<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4b7o400g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e4b7o400g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:corner-right-down-line" /></template>

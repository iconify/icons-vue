<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdihez-4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xdihez-4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bomb-line" /></template>

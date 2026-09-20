<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vel3fvbkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vel3fvbkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chinese-knot-line" /></template>

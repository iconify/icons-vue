<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxlmmx9sx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oxlmmx9sx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:clock-7-line" /></template>

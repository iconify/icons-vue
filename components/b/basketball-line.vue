<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x26zr_bjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x26zr_bjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:basketball-line" /></template>

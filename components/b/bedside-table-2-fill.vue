<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vl38k0bkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vl38k0bkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bedside-table-2-fill" /></template>

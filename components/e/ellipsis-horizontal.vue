<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwy2peqdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fwy2peqdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:ellipsis-horizontal" /></template>

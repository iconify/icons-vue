<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdjnet7ze.css';
import '../../css/v/vmbrozb2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mdjnet7ze"/><path class="vmbrozb2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:arrowhead-left-outline" /></template>

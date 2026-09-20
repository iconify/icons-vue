<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mpue87gvs.css';
import '../../css/i/iezp-tb3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mpue87gvs"/><path class="iezp-tb3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:cloud-warning-bold" /></template>

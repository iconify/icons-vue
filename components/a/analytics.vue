<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhsg9bc_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mhsg9bc_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:analytics" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_hx_ibsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_hx_ibsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:arrow-big-down-dash-filled" /></template>

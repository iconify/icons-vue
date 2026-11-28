<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0vuqx_ps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d0vuqx_ps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:check-circle" /></template>

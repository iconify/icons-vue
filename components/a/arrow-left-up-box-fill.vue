<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_hndv8xy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d_hndv8xy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:arrow-left-up-box-fill" /></template>

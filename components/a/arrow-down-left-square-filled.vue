<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2ii_ey5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s2ii_ey5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-down-left-square-filled" /></template>

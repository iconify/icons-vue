<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwtr5_pps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lwtr5_pps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-dog-solid" /></template>

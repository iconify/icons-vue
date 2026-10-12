<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3c95uabp.css';
import '../../css/u/upue2acrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l3c95uabp"/><path class="upue2acrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:calendar-plus-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fsr_drbgn.css';
import '../../css/p/pfaueebia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fsr_drbgn"/><path class="pfaueebia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:edit-20-bold" /></template>

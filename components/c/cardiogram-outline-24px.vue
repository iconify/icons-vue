<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cu5w9ebgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cu5w9ebgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:cardiogram-outline-24px" /></template>

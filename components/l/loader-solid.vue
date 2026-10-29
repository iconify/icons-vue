<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kdnluabmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kdnluabmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:loader-solid" /></template>

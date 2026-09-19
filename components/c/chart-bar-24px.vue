<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fvdy0ubkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fvdy0ubkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:chart-bar-24px" /></template>

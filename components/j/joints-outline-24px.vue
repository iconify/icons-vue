<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ct6yfj32v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ct6yfj32v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:joints-outline-24px" /></template>

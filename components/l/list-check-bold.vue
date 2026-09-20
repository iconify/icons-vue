<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rtz_hcc5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rtz_hcc5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:list-check-bold" /></template>

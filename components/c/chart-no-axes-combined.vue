<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/npsi0gptz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="npsi0gptz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:chart-no-axes-combined" /></template>

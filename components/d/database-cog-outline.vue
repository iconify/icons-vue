<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tq2lx5x1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tq2lx5x1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:database-cog-outline" /></template>

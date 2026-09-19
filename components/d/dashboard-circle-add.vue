<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z13w5zg4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z13w5zg4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:dashboard-circle-add" /></template>

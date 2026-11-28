<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpjk8pbbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lpjk8pbbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:dashboard-gear" /></template>

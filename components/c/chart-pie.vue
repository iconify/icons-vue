<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzjr0cb5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dzjr0cb5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:chart-pie" /></template>

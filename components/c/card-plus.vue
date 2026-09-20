<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/syg-rq9ew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="syg-rq9ew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:card-plus" /></template>

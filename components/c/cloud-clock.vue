<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7n7n7t2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p7n7n7t2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cloud-clock" /></template>

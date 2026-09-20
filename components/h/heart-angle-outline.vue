<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a8nyh_6nc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a8nyh_6nc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:heart-angle-outline" /></template>

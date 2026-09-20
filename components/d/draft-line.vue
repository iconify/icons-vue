<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vy6bvdbas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vy6bvdbas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:draft-line" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_4fezbjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d_4fezbjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:ambulance" /></template>

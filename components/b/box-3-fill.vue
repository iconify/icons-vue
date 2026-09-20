<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oocirobjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oocirobjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:box-3-fill" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dem4o0bsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dem4o0bsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bed-empty" /></template>

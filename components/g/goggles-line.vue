<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bo_v0662r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bo_v0662r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:goggles-line" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iy3oz7v9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iy3oz7v9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:add-fill" /></template>

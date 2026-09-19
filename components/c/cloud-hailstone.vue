<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ud2ydveto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ud2ydveto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:cloud-hailstone" /></template>

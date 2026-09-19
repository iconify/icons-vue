<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/g/g8qfvnbjm.css';
import '../../css/d/d6ip8mb4m.css';
import '../../css/s/sj6rsfbex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="g8qfvnbjm"/><path class="d6ip8mb4m"/><path class="sj6rsfbex"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:crosshair" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mv_j_db-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mv_j_db-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:door-closed" /></template>

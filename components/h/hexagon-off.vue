<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ksa7z7pcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ksa7z7pcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:hexagon-off" /></template>

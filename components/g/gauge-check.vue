<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pr-lowb7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pr-lowb7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:gauge-check" /></template>

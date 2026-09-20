<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjdxl-bov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jjdxl-bov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:baby-buggy-off" /></template>

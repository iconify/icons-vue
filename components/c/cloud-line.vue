<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j82ljlhri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j82ljlhri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:cloud-line" /></template>

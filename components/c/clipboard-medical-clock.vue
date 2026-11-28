<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kocx10j0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kocx10j0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:clipboard-medical-clock" /></template>

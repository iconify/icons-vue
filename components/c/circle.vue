<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbzua0bpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lbzua0bpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:circle" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p319hddsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p319hddsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:bookmark-active" /></template>
